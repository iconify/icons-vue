<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n900g9b9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n900g9b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:favicon" /></template>
