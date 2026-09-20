<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8331sb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j8331sb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:list-graphics-text" /></template>
