<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxhbwqfms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="cxhbwqfms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:appcelerator-wordmark" /></template>
