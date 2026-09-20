<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdn5rpciy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdn5rpciy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:display-line" /></template>
