<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w63tedcfl.css';
import '../../css/f/f_2qjsb7v.css';
import '../../css/n/nc19r8l8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="w63tedcfl"/><path class="f_2qjsb7v"/><path class="nc19r8l8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:eslint-wordmark" /></template>
