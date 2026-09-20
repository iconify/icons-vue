<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qczze5bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="qczze5bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:highlighter-2" /></template>
