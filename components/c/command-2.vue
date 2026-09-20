<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-ml_tw3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-ml_tw3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber-color:command-2" /></template>
