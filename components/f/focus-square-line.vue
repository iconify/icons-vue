<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_er4bapv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_er4bapv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:focus-square-line" /></template>
