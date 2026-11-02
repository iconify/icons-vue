<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo06xufmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vo06xufmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heavy-rainstorm-line" /></template>
