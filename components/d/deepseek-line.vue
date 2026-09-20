<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwcieybdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwcieybdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:deepseek-line" /></template>
