<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2idrrb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="q2idrrb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:bakery-14" /></template>
