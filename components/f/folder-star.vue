<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_yl57rvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_yl57rvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:folder-star" /></template>
