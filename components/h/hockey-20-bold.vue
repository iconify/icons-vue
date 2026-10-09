<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejrj45bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ejrj45bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hockey-20-bold" /></template>
