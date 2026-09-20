<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o43r2_blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o43r2_blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:house-damage" /></template>
