<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3cemgbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f3cemgbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:foot" /></template>
