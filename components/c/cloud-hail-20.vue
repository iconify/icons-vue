<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwfe8ub8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mwfe8ub8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-hail-20" /></template>
