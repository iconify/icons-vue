<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhdo1yb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nhdo1yb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:arrow-up" /></template>
