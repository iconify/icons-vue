<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ils33xbkf.css';
import '../../css/m/mv-f1_b6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ils33xbkf"/><path class="mv-f1_b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:book-marked-20" /></template>
