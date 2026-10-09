<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze-vj538g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ze-vj538g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clouds-20-bold" /></template>
