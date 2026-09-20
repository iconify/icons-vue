<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhc-xmblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhc-xmblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:function-ai-line" /></template>
