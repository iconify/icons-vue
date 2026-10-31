<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/r/ro-7vx6gr.css';
import '../../css/c/c-4bxlqbo.css';
import '../../css/d/dgb8buxbt.css';
import '../../css/s/sy15m6baj.css';
import '../../css/m/mumunvynv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="ro-7vx6gr wm-shadow"/><path class="c-4bxlqbo wm-shadow"/><path class="dgb8buxbt"/><path class="sy15m6baj"/><path class="mumunvynv wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:cloud-upload" /></template>
