<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/way5rg2jx.css';
import '../../css/s/sxsjrzbyv.css';
import '../../css/q/qq05izhzw.css';
import '../../css/v/v46awac6b.css';
import '../../css/b/byabkegeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="way5rg2jx"/><g class="sxsjrzbyv"><path clip-rule="evenodd" class="qq05izhzw"/><path clip-rule="evenodd" class="v46awac6b"/><path class="byabkegeg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:japanese-monthly-amount-button" /></template>
