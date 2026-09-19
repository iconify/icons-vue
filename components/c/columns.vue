<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlwlwjbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1536};
const content = `<path class="wlwlwjbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:columns" /></template>
