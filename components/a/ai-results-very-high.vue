<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8_timb4b.css';
import '../../css/k/kjn-utb6c.css';
import '../../css/r/rw3u8dcyu.css';
import '../../css/s/s3bjnib6t.css';
import '../../css/c/cytj3kbqo.css';
import '../../css/f/ftpj2s7sw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c8_timb4b"/><path class="kjn-utb6c"/><path class="rw3u8dcyu"/><path class="s3bjnib6t"/><path class="cytj3kbqo"/><path class="ftpj2s7sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ai-results-very-high" /></template>
