<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-cry_4vx.css';
import '../../css/p/p_obrx4cs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f-cry_4vx"/><path class="p_obrx4cs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-bookmark" /></template>
