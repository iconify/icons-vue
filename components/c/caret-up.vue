<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfjmi0btm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfjmi0btm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:caret-up" /></template>
