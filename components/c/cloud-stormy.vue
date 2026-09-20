<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9725xb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l9725xb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:cloud-stormy" /></template>
