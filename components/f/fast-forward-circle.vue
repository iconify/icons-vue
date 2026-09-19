<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqbkv8u2i.css';
import '../../css/e/et8b16b_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqbkv8u2i"/><path class="et8b16b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:fast-forward-circle" /></template>
