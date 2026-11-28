<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjrf6i_zq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjrf6i_zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:book-marked-solid" /></template>
