<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc55xbcub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc55xbcub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:captions-fill" /></template>
