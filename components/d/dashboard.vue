<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hng5s4j4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="hng5s4j4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:dashboard" /></template>
