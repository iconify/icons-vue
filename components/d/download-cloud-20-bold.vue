<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4q0sxn6x.css';
import '../../css/p/p-3dudb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y4q0sxn6x"/><path class="p-3dudb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:download-cloud-20-bold" /></template>
