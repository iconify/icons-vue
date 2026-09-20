<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd9m6dbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd9m6dbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:bullet-point" /></template>
