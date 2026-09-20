<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyez6_ixh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyez6_ixh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hotkey-fill" /></template>
