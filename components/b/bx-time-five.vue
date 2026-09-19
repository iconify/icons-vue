<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqbkv8u2i.css';
import '../../css/x/x9y4r4l6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqbkv8u2i"/><path class="x9y4r4l6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-time-five" /></template>
