<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyafseb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyafseb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:letters-k" /></template>
