<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqbkv8u2i.css';
import '../../css/q/q5iakzbgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqbkv8u2i"/><path class="q5iakzbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-bolt-circle" /></template>
