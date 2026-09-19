<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drmnp89cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="drmnp89cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-badge-fill-12" /></template>
