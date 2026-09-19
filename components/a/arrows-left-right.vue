<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiuiq63rg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qiuiq63rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrows-left-right" /></template>
