<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q28y73oat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q28y73oat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:accessibility-fill-20" /></template>
