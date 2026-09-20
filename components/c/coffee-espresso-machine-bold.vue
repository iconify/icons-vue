<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lglvlnxox.css';
import '../../css/k/ktnt72cco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lglvlnxox"/><path class="ktnt72cco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:coffee-espresso-machine-bold" /></template>
