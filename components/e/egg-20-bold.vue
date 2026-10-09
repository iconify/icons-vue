<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7cj1cc1l.css';
import '../../css/e/exm6e72le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v7cj1cc1l"/><path class="exm6e72le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:egg-20-bold" /></template>
