<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed45f58pb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ed45f58pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:gnuradio-wordmark" /></template>
