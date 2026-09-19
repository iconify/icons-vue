<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itkxm1eaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itkxm1eaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-exit-fullscreen" /></template>
