<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmi280ire.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmi280ire"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:az-sort-ascending-letters-line" /></template>
