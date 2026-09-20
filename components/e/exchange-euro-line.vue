<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrjcy4b3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrjcy4b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:exchange-euro-line" /></template>
