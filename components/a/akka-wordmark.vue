<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4-vqrbre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="g4-vqrbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:akka-wordmark" /></template>
