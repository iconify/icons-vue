<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdlpnnk8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pdlpnnk8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:format-bold" /></template>
