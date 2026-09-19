<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx_vtdb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cx_vtdb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:fx-tag-solid" /></template>
