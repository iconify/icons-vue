<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9qaknzwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="m9qaknzwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:decline-call" /></template>
