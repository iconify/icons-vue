<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kc784jy4i.css';
import '../../css/d/d-7w0ebsy.css';
import '../../css/c/cri_8d0jy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="kc784jy4i"/><path class="d-7w0ebsy"/><path class="cri_8d0jy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:adjacent-item" /></template>
