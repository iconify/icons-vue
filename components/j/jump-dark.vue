<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9j50ebdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o9j50ebdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jump-dark" /></template>
