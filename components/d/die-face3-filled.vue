<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0uqw6imm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="j0uqw6imm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:die-face3-filled" /></template>
