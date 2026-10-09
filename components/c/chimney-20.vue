<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhjg018pp.css';
import '../../css/a/a0pyaabma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fhjg018pp"/><path class="a0pyaabma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chimney-20" /></template>
