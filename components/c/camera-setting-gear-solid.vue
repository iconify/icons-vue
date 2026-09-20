<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwo6jxbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iwo6jxbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:camera-setting-gear-solid" /></template>
