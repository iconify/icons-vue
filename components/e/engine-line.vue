<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xaia0tblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xaia0tblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:engine-line" /></template>
