<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpd5dzuzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lpd5dzuzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:dark-display-mode-solid" /></template>
