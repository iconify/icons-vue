<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5pt64b6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i5pt64b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fetus-in-circle" /></template>
