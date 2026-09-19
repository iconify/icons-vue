<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lglub4bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lglub4bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:fork-node" /></template>
