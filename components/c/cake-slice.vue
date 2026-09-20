<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxea29b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="nxea29b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cake-slice" /></template>
