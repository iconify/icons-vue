<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2z_0u2cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h2z_0u2cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:adjust" /></template>
