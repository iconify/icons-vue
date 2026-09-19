<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyvqkcc0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="dyvqkcc0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:caret-square-left" /></template>
