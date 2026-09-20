<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrjjpabrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jrjjpabrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:location-pin-medical-hospital-2-solid" /></template>
