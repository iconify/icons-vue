<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmcsts5zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tmcsts5zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:home-4-solid" /></template>
