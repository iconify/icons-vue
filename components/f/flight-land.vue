<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jals4jjxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":416};
const content = `<path class="jals4jjxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:flight-land" /></template>
