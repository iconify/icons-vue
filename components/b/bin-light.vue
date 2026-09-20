<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erzf03bmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="erzf03bmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bin-light" /></template>
