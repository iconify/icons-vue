<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9ly-n7ye.css';
import '../../css/d/dzz1crbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n9ly-n7ye"/><path class="dzz1crbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-sun-rain-20-bold" /></template>
