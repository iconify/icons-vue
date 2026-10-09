<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjazr7byc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qjazr7byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-drizzle-20-bold" /></template>
