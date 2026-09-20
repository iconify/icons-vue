<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsxl87bvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bsxl87bvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:home-1-remix" /></template>
