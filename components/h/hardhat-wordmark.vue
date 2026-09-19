<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_668e8lv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="x_668e8lv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:hardhat-wordmark" /></template>
