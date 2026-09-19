<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs-iz4qkj.css';
import '../../css/o/oqygufz8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qs-iz4qkj"/><path class="oqygufz8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:linkedin" /></template>
