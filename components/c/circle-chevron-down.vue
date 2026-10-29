<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csivk-nbx.css';
import '../../css/z/znu966bzc.css';
import '../../css/z/zjm716l0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csivk-nbx wm-k"/><path class="wm-a znu966bzc"/><path class="wm-a zjm716l0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:circle-chevron-down" /></template>
