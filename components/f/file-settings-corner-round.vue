<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zllshdcyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zllshdcyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-settings-corner-round" /></template>
