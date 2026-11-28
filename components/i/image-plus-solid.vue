<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/toc5u-bdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="toc5u-bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:image-plus-solid" /></template>
