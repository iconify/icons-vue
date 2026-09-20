<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mstsl-byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mstsl-byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:euro-waves-solid" /></template>
