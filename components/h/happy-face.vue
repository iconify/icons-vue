<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hms937aej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hms937aej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:happy-face" /></template>
