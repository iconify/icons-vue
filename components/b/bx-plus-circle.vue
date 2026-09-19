<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e78vbih2x.css';
import '../../css/w/wqbkv8u2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e78vbih2x"/><path class="wqbkv8u2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-plus-circle" /></template>
