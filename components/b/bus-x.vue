<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfcoj9b5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfcoj9b5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bus-x" /></template>
