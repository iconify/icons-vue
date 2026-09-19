<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/k/kgoe69b6c.css';
import '../../css/i/iu5_1fbyz.css';
import '../../css/e/enlxepbgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><circle class="kgoe69b6c"/><circle class="iu5_1fbyz"/><circle class="enlxepbgk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:ellipsis-outline" /></template>
