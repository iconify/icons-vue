<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o8pl2ybmn.css';
import '../../css/c/cvrrw4eax.css';
import '../../css/m/mtszgmo6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="o8pl2ybmn"/><path class="cvrrw4eax"/><path class="mtszgmo6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:dumpling" /></template>
