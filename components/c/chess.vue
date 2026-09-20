<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi_rclbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xi_rclbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:chess" /></template>
