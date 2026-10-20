<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpnv-nbzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpnv-nbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:group" /></template>
