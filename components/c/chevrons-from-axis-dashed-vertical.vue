<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsf3-rhca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsf3-rhca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chevrons-from-axis-dashed-vertical" /></template>
