<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot-8v9bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ot-8v9bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:juce" /></template>
