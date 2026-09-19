<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdp02hb8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":24};
const content = `<path class="wdp02hb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:atom" /></template>
