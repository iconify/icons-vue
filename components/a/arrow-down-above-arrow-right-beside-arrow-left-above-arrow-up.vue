<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk-do6bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fk-do6bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-down-above-arrow-right-beside-arrow-left-above-arrow-up" /></template>
