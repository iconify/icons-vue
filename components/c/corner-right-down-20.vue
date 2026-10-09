<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlocb6bmt.css';
import '../../css/d/dhj1chemz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dlocb6bmt"/><path class="dhj1chemz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-right-down-20" /></template>
