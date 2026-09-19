<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0b2bvsvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="f0b2bvsvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:asterisk" /></template>
