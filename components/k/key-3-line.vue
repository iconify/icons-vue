<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddeipvo2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddeipvo2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:key-3-line" /></template>
