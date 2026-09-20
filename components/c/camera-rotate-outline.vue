<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yul2wvb3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yul2wvb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:camera-rotate-outline" /></template>
