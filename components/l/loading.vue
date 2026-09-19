<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf-3mxbdo.css';
import '../../css/e/enhfi_bcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jf-3mxbdo"/><path class="enhfi_bcu"><animateTransform attributeName="transform" dur="1s" from="0 12 12" repeatCount="indefinite" to="360 12 12" type="rotate"/></path>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:loading" /></template>
