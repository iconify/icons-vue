<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss38_lbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ss38_lbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:magnifying-glass-plus" /></template>
