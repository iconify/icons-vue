<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn7_7837p.css';
import '../../css/m/mjr421z4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kn7_7837p"/><path class="mjr421z4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:archive-stroke-20" /></template>
