<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/defsf5bjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="defsf5bjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:format-italic" /></template>
