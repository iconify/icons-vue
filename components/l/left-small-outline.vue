<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke_s0c99d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ke_s0c99d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:left-small-outline" /></template>
