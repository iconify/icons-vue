<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ievlno-9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ievlno-9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:equal-math-symbol-circle-bold" /></template>
