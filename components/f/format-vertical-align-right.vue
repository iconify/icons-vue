<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txgaijbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txgaijbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:format-vertical-align-right" /></template>
