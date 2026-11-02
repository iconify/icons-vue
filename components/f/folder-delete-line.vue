<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxxuu8u_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxxuu8u_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-delete-line" /></template>
