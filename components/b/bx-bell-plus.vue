<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5f0tenvo.css';
import '../../css/j/j2ldz72eb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5f0tenvo"/><path class="j2ldz72eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-bell-plus" /></template>
