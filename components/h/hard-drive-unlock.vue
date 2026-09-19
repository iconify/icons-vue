<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx0dpu8wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zx0dpu8wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:hard-drive-unlock" /></template>
