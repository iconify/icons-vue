<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afxmlpbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afxmlpbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:drill-check" /></template>
