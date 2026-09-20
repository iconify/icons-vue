<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2jr2o6cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2jr2o6cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:id-card-sharp" /></template>
