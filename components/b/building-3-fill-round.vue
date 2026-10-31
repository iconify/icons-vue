<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcnuuetab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcnuuetab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-3-fill-round" /></template>
