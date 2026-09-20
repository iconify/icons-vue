<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqt9uxmcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqt9uxmcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:clerk" /></template>
