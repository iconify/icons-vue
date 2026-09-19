<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0i0_d7-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="v0i0_d7-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:burst" /></template>
