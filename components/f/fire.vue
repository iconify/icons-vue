<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh0myxh6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yh0myxh6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:fire" /></template>
