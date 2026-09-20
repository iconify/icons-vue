<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfgzsf_mw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfgzsf_mw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:drawing-board-line" /></template>
