<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvxoq3cbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvxoq3cbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:dollar-sign-filled" /></template>
