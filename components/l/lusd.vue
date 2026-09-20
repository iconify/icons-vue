<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq0u8kb-s.css';
import '../../css/x/xo6cg7b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq0u8kb-s"/><path class="xo6cg7b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lusd" /></template>
