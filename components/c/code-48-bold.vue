<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzjvwvyqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tzjvwvyqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:code-48-bold" /></template>
