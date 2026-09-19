<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osd0djzhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="osd0djzhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:framermotion-wordmark" /></template>
