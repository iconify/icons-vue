<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhx2a_1cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhx2a_1cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-headphones-line" /></template>
