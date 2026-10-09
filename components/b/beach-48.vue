<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxy5wbcie.css';
import '../../css/c/clh0ambgx.css';
import '../../css/w/wfx3nk7mg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oxy5wbcie"/><path class="clh0ambgx"/><path class="wfx3nk7mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:beach-48" /></template>
