<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds6kzrfzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ds6kzrfzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:earbuds-48-bold" /></template>
