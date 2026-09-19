<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7ee_c0lu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l7ee_c0lu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:clockwiseleftrightarrows" /></template>
