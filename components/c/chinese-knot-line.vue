<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d999a1bfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d999a1bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chinese-knot-line" /></template>
