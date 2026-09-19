<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6nhtqbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="r6nhtqbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:eyedropper" /></template>
