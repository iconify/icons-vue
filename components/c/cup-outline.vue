<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q77s72bme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q77s72bme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:cup-outline" /></template>
