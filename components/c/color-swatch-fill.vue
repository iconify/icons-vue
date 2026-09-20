<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjc3tibnp.css';
import '../../css/d/dacej6b-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjc3tibnp"/><path class="dacej6b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:color-swatch-fill" /></template>
