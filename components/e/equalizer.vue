<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohz7-3zmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ohz7-3zmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:equalizer" /></template>
