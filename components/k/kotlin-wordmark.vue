<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp-3b16-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qp-3b16-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:kotlin-wordmark" /></template>
