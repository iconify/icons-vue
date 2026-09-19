<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjzy66b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qjzy66b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:foundation-wordmark" /></template>
