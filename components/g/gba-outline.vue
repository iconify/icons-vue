<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4jo3rb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d4jo3rb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:gba-outline" /></template>
