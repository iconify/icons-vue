<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2abq7bcp.css';
import '../../css/i/i10p98n8s.css';
import '../../css/x/xp0k47luu.css';
import '../../css/o/o2lq3ybcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s2abq7bcp"/><g class="i10p98n8s"><path class="xp0k47luu"/><circle class="o2lq3ybcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:library" /></template>
