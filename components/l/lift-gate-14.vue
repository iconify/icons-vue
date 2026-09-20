<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlh4vhbep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zlh4vhbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:lift-gate-14" /></template>
