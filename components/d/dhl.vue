<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tau-3srte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="tau-3srte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:dhl" /></template>
