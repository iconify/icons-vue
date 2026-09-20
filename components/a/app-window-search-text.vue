<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/o/ol3qevala.css';
import '../../css/q/qlbh4ybeo.css';
import '../../css/k/kl16iub3v.css';
import '../../css/w/wvla7xgat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ol3qevala"/><path class="qlbh4ybeo"/><path class="kl16iub3v"/><path class="wvla7xgat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:app-window-search-text" /></template>
