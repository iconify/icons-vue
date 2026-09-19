<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgxe34zhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pgxe34zhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:codeigniter-wordmark" /></template>
