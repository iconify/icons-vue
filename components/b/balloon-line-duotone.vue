<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/sxio5cbij.css';
import '../../css/a/a0ykk1jag.css';
import '../../css/z/z9r7w0b0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sxio5cbij"/><path class="a0ykk1jag"/><path class="z9r7w0b0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:balloon-line-duotone" /></template>
