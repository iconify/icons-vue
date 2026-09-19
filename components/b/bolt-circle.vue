<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t91s7oy2f.css';
import '../../css/u/uti5_1b8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t91s7oy2f"/><path class="uti5_1b8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:bolt-circle" /></template>
