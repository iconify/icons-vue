<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlre_ubfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlre_ubfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-warning-line" /></template>
