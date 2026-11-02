<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yubdtabdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yubdtabdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrows-up-from-line-line" /></template>
