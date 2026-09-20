<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcmrdvhow.css';
import '../../css/h/hzunv164j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dcmrdvhow"/><path class="hzunv164j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:atom" /></template>
