<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee-uncc2s.css';
import '../../css/z/z33pz2bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ee-uncc2s"/><path class="z33pz2bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:fiber" /></template>
