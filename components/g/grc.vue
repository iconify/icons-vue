<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_i1oy07h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r_i1oy07h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:grc" /></template>
