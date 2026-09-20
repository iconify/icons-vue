<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jluaz1kbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="jluaz1kbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:cowboy" /></template>
