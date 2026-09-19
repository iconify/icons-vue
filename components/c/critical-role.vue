<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmu515hrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="fmu515hrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:critical-role" /></template>
