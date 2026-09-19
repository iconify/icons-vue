<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sos2nmbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="sos2nmbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:datadog-wordmark" /></template>
