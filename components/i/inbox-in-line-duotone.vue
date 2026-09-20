<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/m06nw7mgj.css';
import '../../css/r/ribhzvbcl.css';
import '../../css/f/f-srkbcuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m06nw7mgj"/><path class="ribhzvbcl"/><path class="f-srkbcuc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:inbox-in-line-duotone" /></template>
