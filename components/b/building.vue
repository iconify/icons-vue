<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/texanzbed.css';
import '../../css/f/fmf3k-28m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer texanzbed"/><path class="duoicon-primary-layer fmf3k-28m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:building" /></template>
