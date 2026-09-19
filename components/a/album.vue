<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t91s7oy2f.css';
import '../../css/w/w7en3fx7q.css';
import '../../css/a/axk22gbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t91s7oy2f"/><path class="w7en3fx7q"/><path class="axk22gbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:album" /></template>
