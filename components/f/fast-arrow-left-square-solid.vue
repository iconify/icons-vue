<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahnbmtbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ahnbmtbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:fast-arrow-left-square-solid" /></template>
