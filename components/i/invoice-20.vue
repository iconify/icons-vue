<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re0n-jb1b.css';
import '../../css/m/myvzpbcde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="re0n-jb1b"/><path class="myvzpbcde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:invoice-20" /></template>
