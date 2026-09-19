<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0u060rxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v0u060rxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:blackmediumsmallsquare" /></template>
