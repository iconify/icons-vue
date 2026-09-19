<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fehcr6bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="fehcr6bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:airline-seat-individual-suite" /></template>
