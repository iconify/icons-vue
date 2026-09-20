<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbuwyijec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="tbuwyijec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:departure-time" /></template>
