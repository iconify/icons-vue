<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1x_6zbkv.css';
import '../../css/n/ndsoh9bgy.css';
import '../../css/k/k1usvwtey.css';
import '../../css/k/k7y_74pjq.css';
import '../../css/h/hdcj5fbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="d1x_6zbkv"/><path class="ndsoh9bgy"/><path class="k1usvwtey"/><path class="k7y_74pjq"/><path class="hdcj5fbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:iraq" /></template>
