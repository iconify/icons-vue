<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci7_qzgce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ci7_qzgce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cargobike-and-locked-lock-with-keyhole" /></template>
