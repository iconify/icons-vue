<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3xtuk_0z.css';
import '../../css/f/fjtgj3buw.css';
import '../../css/z/zff2_4bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="l3xtuk_0z"><path class="fjtgj3buw"/><path class="zff2_4bao"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:bluetooth-searching" /></template>
