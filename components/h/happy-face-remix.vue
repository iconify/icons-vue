<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np5g_yzxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="np5g_yzxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:happy-face-remix" /></template>
