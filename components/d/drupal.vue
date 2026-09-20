<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru-z4wb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru-z4wb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:drupal" /></template>
