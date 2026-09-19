<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnnlgvb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="jnnlgvb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:high-speed-train" /></template>
