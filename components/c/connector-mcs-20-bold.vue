<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0xk1spxw.css';
import '../../css/r/rl8wzi39v.css';
import '../../css/m/mv-u1xbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i0xk1spxw"/><path class="rl8wzi39v"/><path class="mv-u1xbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:connector-mcs-20-bold" /></template>
