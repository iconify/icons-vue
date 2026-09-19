<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3gh1kbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o3gh1kbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:cat-footprint" /></template>
