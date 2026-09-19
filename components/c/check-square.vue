<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4-i4ybyx.css';
import '../../css/c/c98at3bul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4-i4ybyx"/><path class="c98at3bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:check-square" /></template>
