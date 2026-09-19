<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/t/tqw8k0f0r.css';
import '../../css/u/un_5co41a.css';
import '../../css/n/n0_i2bckx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><circle class="tqw8k0f0r"/><path class="un_5co41a"/><circle class="n0_i2bckx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:cd" /></template>
