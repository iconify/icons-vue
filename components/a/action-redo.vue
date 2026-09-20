<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oevl6j0cm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="oevl6j0cm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:action-redo" /></template>
