<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj7ykkl-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nj7ykkl-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:crop-outline" /></template>
