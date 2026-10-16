<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycd8zvvjv.css';
import '../../css/c/c9il3frxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ycd8zvvjv"/><path class="c9il3frxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:glue-gun-48" /></template>
