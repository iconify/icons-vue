<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz21tryay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nz21tryay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:auto-correction-check-solid" /></template>
