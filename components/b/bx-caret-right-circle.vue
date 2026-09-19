<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkamcyd2s.css';
import '../../css/w/wqbkv8u2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkamcyd2s"/><path class="wqbkv8u2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-caret-right-circle" /></template>
