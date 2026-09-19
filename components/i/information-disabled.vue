<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/outcig9zn.css';
import '../../css/i/i0orfx9cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="outcig9zn"/><path class="i0orfx9cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:information-disabled" /></template>
