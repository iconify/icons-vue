<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5mnzse4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="d5mnzse4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:closed-caption" /></template>
