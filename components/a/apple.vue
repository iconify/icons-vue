<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwtp_-bzj.css';
import '../../css/h/h3mkp0b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer xwtp_-bzj"/><path class="duoicon-primary-layer h3mkp0b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:apple" /></template>
