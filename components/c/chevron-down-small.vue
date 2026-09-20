<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j23jfj2cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="j23jfj2cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:chevron-down-small" /></template>
