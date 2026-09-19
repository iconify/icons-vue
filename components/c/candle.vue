<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6xnufbol.css';
import '../../css/j/jtlquzbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6xnufbol duoicon-primary-layer"/><path class="duoicon-secondary-layer jtlquzbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:candle" /></template>
