<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqozz7blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqozz7blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:filter-check" /></template>
