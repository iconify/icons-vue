<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmk60pbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmk60pbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:forward-fill" /></template>
