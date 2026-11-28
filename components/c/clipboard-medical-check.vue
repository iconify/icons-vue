<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clz-cx4ji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clz-cx4ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:clipboard-medical-check" /></template>
