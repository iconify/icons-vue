<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxplhebtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gxplhebtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-bottom-left-on-square-20-solid" /></template>
