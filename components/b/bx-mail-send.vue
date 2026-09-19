<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8wh6ihst.css';
import '../../css/c/cd1qz4bbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8wh6ihst"/><path class="cd1qz4bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-mail-send" /></template>
