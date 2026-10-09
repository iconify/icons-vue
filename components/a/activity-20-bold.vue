<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9w7clzrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s9w7clzrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:activity-20-bold" /></template>
