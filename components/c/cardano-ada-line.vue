<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfzhtmbxu.css';
import '../../css/b/bmz0dzmey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfzhtmbxu"/><path class="bmz0dzmey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cardano-ada-line" /></template>
