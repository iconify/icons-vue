<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-9o0_b7b.css';
import '../../css/k/ka84qdbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="d-9o0_b7b"/><path class="ka84qdbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:keras" /></template>
