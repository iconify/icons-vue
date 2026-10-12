<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf_kpfbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yf_kpfbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:clock-5-filled" /></template>
