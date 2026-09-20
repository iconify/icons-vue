<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb2ecghwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="wb2ecghwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:card-view" /></template>
