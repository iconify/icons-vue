<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ameq29b2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ameq29b2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:elasticsearch-wordmark" /></template>
