<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohbpjk02c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":630,"height":700};
const content = `<path class="ohbpjk02c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:arrow-down" /></template>
