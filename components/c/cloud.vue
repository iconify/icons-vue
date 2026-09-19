<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dumv5nw4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="dumv5nw4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:cloud" /></template>
