<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tut9witox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tut9witox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-download-alt" /></template>
