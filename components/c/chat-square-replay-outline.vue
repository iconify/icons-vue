<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad5234bxv.css';
import '../../css/u/um_zvyb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad5234bxv"/><path clip-rule="evenodd" class="um_zvyb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-replay-outline" /></template>
