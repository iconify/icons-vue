<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvnprs7bd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xvnprs7bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:inbox-tray-1" /></template>
