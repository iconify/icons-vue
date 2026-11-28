<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdze-ty3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdze-ty3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:layers-arrow-down-solid" /></template>
