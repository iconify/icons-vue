<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xikok5biz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xikok5biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:attic-assets-light" /></template>
