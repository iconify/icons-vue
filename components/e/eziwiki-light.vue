<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9a0a3bkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g9a0a3bkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:eziwiki-light" /></template>
