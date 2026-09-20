<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr1k-tbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nr1k-tbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:fingerprint-1-solid" /></template>
