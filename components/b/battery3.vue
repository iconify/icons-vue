<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rom9c69aj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rom9c69aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:battery3" /></template>
