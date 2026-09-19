<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds858oo5g.css';
import '../../css/w/wqbkv8u2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds858oo5g"/><path class="wqbkv8u2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-heart-circle" /></template>
