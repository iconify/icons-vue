<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh6wegb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uh6wegb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clipboard-paste-fill" /></template>
