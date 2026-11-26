<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e13j-rb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="e13j-rb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:directx-wordmark" /></template>
