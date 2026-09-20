<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsee2mmqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsee2mmqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:cursor-select-area" /></template>
