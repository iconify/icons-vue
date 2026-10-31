<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/volfzd5cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="volfzd5cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:id-card-fill-round" /></template>
