<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5-l4ub-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="m5-l4ub-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:gnome" /></template>
