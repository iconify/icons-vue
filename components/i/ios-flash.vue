<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz8zq1ysl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rz8zq1ysl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-flash" /></template>
