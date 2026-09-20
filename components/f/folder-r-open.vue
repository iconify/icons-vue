<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh0zkx8bv.css';
import '../../css/y/yud54w-4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jh0zkx8bv"/><path class="yud54w-4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-r-open" /></template>
