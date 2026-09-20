<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/y9s618baa.css';
import '../../css/e/ez9x9wbch.css';
import '../../css/y/y-18oobhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y9s618baa"/><path class="ez9x9wbch"/><path class="y-18oobhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-horizontal-spacing-linear" /></template>
