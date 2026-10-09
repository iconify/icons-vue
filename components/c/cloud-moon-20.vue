<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe3d6k5kz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oe3d6k5kz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-moon-20" /></template>
