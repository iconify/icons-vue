<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqby4c3ii.css';
import '../../css/s/sz385ccax.css';
import '../../css/p/pofuqcb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gqby4c3ii"/><path class="sz385ccax"/><path class="pofuqcb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:freezing-rain-20" /></template>
