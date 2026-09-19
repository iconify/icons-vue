<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rufo9cbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="rufo9cbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:gauge-med" /></template>
