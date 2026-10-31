<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/f/fw22vcbnw.css';
import '../../css/x/xd0veabmf.css';
import '../../css/n/n3jvmegul.css';
import '../../css/j/ju4zm1b1x.css';
import '../../css/a/a0o9nky4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="fw22vcbnw"/><path class="wm-shine xd0veabmf"/><path class="n3jvmegul wm-k"/><path class="ju4zm1b1x wm-a"/><path class="a0o9nky4v wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:file-pdf" /></template>
