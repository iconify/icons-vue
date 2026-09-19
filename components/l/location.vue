<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0egwfhfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g0egwfhfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:location" /></template>
