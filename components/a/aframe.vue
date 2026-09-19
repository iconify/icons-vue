<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6j2i1bzb.css';
import '../../css/n/nwa55i2nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="f6j2i1bzb"/><path class="nwa55i2nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:aframe" /></template>
