<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrjwoobuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrjwoobuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrows-expand-expressive" /></template>
