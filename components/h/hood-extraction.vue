<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn9pt63aj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bn9pt63aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:hood-extraction" /></template>
