<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caj3s8vnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="caj3s8vnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:door-open" /></template>
