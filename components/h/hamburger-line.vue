<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruu9vi6cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruu9vi6cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hamburger-line" /></template>
