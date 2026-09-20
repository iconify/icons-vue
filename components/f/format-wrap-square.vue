<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-76m0b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-76m0b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:format-wrap-square" /></template>
