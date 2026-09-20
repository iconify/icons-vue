<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsp0khbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dsp0khbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bubble" /></template>
