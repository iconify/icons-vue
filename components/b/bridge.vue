<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlnf44bvp.css';
import '../../css/n/nfe2dnbyj.css';
import '../../css/q/qx-gz1b8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer hlnf44bvp"/><path class="duoicon-secondary-layer nfe2dnbyj"/><path class="duoicon-primary-layer qx-gz1b8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:bridge" /></template>
