<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/i/i8fgxnb-f.css';
import '../../css/y/y4s1wobbc.css';
import '../../css/o/obqcm0o_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="i8fgxnb-f"/><path class="y4s1wobbc"/><path class="obqcm0o_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:fingerprint" /></template>
