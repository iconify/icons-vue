<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux23lm17f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ux23lm17f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:apachekafka-wordmark" /></template>
