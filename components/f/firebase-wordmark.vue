<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd9c_2bin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qd9c_2bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:firebase-wordmark" /></template>
