<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avg_rrboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="avg_rrboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:k6" /></template>
