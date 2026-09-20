<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlfa8cbym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rlfa8cbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:compass2-filled" /></template>
