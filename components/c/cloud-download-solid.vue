<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzypiw3nw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzypiw3nw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cloud-download-solid" /></template>
