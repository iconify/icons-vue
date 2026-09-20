<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0la11bfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c0la11bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bear-spray-can-with-spray-and-ruble" /></template>
