<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvhxrzivp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rvhxrzivp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:fluence" /></template>
