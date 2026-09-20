<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktv_hgbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ktv_hgbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:dumbbells" /></template>
