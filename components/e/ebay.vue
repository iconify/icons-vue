<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9pa2g-6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="n9pa2g-6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:ebay" /></template>
