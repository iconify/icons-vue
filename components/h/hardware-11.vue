<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-ansi1om.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="e-ansi1om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:hardware-11" /></template>
