<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgpl5vbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgpl5vbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-folder-open" /></template>
