<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4sx8_brx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="n4sx8_brx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:ghidra" /></template>
