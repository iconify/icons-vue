<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igjwmybhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":60};
const content = `<path class="igjwmybhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:interfere-light" /></template>
