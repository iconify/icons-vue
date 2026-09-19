<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3o99tboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="x3o99tboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:gear" /></template>
