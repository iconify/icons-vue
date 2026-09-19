<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy8y-8xfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fy8y-8xfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:facebook-f" /></template>
