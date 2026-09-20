<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl30c4zma.css';
import '../../css/n/nm-0yofzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl30c4zma"/><path class="nm-0yofzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:city-filled" /></template>
