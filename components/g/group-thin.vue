<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efue3gdvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="efue3gdvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:group-thin" /></template>
