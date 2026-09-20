<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xra29bcgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xra29bcgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:circle-with-dot" /></template>
