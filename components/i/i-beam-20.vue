<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anroiibuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="anroiibuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:i-beam-20" /></template>
