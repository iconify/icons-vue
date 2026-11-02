<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1jg25bhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1jg25bhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:game-2-line" /></template>
