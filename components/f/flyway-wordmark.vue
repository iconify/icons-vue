<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fept4eb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="fept4eb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:flyway-wordmark" /></template>
