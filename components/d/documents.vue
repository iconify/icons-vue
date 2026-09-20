<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj5bbwbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rj5bbwbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:documents" /></template>
