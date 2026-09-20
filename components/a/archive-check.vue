<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nho5m3r6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nho5m3r6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:archive-check" /></template>
