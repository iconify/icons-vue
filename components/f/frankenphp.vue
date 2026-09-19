<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxvlt1s6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="nxvlt1s6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:frankenphp" /></template>
