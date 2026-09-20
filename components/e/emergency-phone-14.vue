<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/geeit4b4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="geeit4b4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:emergency-phone-14" /></template>
