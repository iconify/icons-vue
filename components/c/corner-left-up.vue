<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdf8a4bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdf8a4bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:corner-left-up" /></template>
