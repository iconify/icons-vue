<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gapw_uyhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gapw_uyhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bus-2-fill" /></template>
