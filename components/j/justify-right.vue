<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru5ry8blp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ru5ry8blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:justify-right" /></template>
