<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfg7b-bee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xfg7b-bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:keras-wordmark" /></template>
