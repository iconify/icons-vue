<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa4oy1b3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oa4oy1b3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:favorite" /></template>
