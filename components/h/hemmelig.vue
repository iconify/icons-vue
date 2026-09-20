<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5r_j7wyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e5r_j7wyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hemmelig" /></template>
