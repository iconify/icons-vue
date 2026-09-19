<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wic510bop.css';
import '../../css/d/dpjsw5bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer wic510bop"/><path class="dpjsw5bva duoicon-primary-layer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:info" /></template>
