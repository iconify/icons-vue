<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqs80qnxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fqs80qnxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:frowning-face-fill" /></template>
