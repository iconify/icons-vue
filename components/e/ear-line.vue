<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iawjtbcfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iawjtbcfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ear-line" /></template>
