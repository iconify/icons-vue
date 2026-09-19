<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu1x4xb0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="mu1x4xb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:buromobelexperte" /></template>
