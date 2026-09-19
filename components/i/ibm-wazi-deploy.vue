<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6na-zfmx.css';
import '../../css/e/evd4z-yaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i6na-zfmx"/><path class="evd4z-yaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-wazi-deploy" /></template>
