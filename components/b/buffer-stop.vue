<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_5l19lqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y_5l19lqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:buffer-stop" /></template>
