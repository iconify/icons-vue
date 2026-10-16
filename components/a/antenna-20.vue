<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h210bm66l.css';
import '../../css/k/k7ytu5blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h210bm66l"/><path class="k7ytu5blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:antenna-20" /></template>
