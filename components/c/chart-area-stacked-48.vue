<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utf77lbef.css';
import '../../css/y/y2skt30fq.css';
import '../../css/v/v-kyi2bll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="utf77lbef"/><path class="y2skt30fq"/><path class="v-kyi2bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-area-stacked-48" /></template>
