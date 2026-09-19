<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5vo40snv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h5vo40snv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:adobe-indesign-solid" /></template>
