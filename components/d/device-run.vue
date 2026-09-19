<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz0f-ub_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="rz0f-ub_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:device-run" /></template>
