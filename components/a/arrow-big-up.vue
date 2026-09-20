<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik0528buj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik0528buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrow-big-up" /></template>
