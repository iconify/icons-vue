<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyl1n9beq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyl1n9beq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrows-expand-left" /></template>
