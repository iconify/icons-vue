<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zawatokrf.css';
import '../../css/l/lb8np0b7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zawatokrf"/><path class="lb8np0b7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:food-drink-fried-chicken" /></template>
