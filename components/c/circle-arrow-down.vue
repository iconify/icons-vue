<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxl6bezbx.css';
import '../../css/z/zzvwx-xsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k yxl6bezbx"/><path class="wm-a zzvwx-xsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:circle-arrow-down" /></template>
