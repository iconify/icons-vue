<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqvox4byg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uqvox4byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:infisical-dark" /></template>
