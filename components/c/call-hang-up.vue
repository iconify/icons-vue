<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqax-6b-d.css';
import '../../css/n/nk5y3tbyy.css';
import '../../css/w/wq7blbcae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="jqax-6b-d"><path class="nk5y3tbyy"/><path class="wq7blbcae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:call-hang-up" /></template>
