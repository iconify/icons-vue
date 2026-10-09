<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k91r7qbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k91r7qbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caret-up-20" /></template>
