<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0bv7wbdk.css';
import '../../css/g/g2_5sshgx.css';
import '../../css/j/j1xfmgbrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="n0bv7wbdk"><path class="g2_5sshgx"/><circle class="j1xfmgbrg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:dub" /></template>
