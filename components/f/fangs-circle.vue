<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dag7f4b9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dag7f4b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fangs-circle" /></template>
