<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn66k4w8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rn66k4w8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:cloud-gear" /></template>
