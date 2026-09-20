<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwg1e6bof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwg1e6bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:depressed-filled" /></template>
