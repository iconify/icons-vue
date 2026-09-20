<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtb38qbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtb38qbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-y-waves-solid" /></template>
