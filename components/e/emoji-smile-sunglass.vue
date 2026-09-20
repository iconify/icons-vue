<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux_-a_76x.css';
import '../../css/h/hdul03-0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux_-a_76x"/><path clip-rule="evenodd" class="hdul03-0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:emoji-smile-sunglass" /></template>
