<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3vt5_b4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z3vt5_b4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:arrow-right" /></template>
