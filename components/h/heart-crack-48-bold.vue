<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5nn_nvzj.css';
import '../../css/y/yrrvfsjve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c5nn_nvzj"/><path class="yrrvfsjve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heart-crack-48-bold" /></template>
