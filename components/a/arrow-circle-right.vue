<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3w_afb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w3w_afb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:arrow-circle-right" /></template>
