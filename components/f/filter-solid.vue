<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfr-x5gls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="tfr-x5gls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:filter-solid" /></template>
