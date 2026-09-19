<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km7b5sb_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="km7b5sb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-right-stroke-12" /></template>
