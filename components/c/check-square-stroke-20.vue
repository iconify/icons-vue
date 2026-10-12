<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrh0vqtny.css';
import '../../css/q/qen7bk-jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hrh0vqtny"/><path class="qen7bk-jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-square-stroke-20" /></template>
