<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhdk_e98b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhdk_e98b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cctv-sharp" /></template>
