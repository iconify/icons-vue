<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwcanry2a.css';
import '../../css/w/wqbkv8u2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwcanry2a"/><path class="wqbkv8u2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:caret-left-circle" /></template>
