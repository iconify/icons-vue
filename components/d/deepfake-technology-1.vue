<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqv-6tbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="kqv-6tbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:deepfake-technology-1" /></template>
