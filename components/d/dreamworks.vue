<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckfu-yb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":38.978};
const content = `<path class="ckfu-yb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dreamworks" /></template>
