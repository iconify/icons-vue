<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz96fzzhj.css';
import '../../css/d/d2kvgvbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVG0kegTdID" class="yz96fzzhj"/></defs><use href="#SVG0kegTdID" transform="translate(4 4)" class="d2kvgvbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:close-outlined" /></template>
