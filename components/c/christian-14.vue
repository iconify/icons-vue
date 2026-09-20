<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nww_-sbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="nww_-sbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:christian-14" /></template>
