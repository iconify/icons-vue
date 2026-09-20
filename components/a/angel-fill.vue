<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j65g2nbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j65g2nbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:angel-fill" /></template>
