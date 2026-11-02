<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uefbi9byy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uefbi9byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:audio-tape-line" /></template>
