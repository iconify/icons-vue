<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hy4bwaboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hy4bwaboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:audio-tape-fill" /></template>
