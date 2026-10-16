<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma-ovdbct.css';
import '../../css/o/o95_lvbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ma-ovdbct"/><path class="o95_lvbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clamp-meter-20-bold" /></template>
