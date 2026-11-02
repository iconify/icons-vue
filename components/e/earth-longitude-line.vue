<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy0sp0bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy0sp0bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:earth-longitude-line" /></template>
