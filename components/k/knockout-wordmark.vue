<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f27cr3b8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="f27cr3b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:knockout-wordmark" /></template>
