<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjs3ttbyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="cjs3ttbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:left-magnifying-glass-filled" /></template>
