<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5xd54bad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="g5xd54bad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:drupal" /></template>
