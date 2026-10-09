<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7t31nbyh.css';
import '../../css/m/ma29g-b3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i7t31nbyh"/><path class="ma29g-b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:alert-20-bold" /></template>
