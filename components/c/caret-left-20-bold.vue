<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr3bl6b0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cr3bl6b0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caret-left-20-bold" /></template>
