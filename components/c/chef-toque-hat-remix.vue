<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l29pplbre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l29pplbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:chef-toque-hat-remix" /></template>
