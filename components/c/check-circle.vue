<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8eq4u5hf.css';
import '../../css/m/mabwzbbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x8eq4u5hf"/><path class="mabwzbbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:check-circle" /></template>
