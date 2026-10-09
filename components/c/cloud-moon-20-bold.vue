<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svglr3bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="svglr3bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-moon-20-bold" /></template>
