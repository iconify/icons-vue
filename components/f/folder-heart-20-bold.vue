<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt8f-3eoh.css';
import '../../css/s/s9tollx4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dt8f-3eoh"/><path class="s9tollx4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-heart-20-bold" /></template>
