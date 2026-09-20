<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-stbsb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j-stbsb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:fast-food-15" /></template>
