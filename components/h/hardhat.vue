<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8zy3dbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8zy3dbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:hardhat" /></template>
