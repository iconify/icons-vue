<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dera1ebbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dera1ebbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ease-in-out-control-point-line" /></template>
