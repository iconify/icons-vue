<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xekxvm7cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xekxvm7cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:anticlockwise-alt-fill" /></template>
