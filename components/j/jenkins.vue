<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r30xk0-2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="r30xk0-2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:jenkins" /></template>
