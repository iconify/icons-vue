<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv48m6brz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cv48m6brz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:checks-solid" /></template>
