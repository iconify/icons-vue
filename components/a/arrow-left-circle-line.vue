<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2y6jdb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2y6jdb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-left-circle-line" /></template>
