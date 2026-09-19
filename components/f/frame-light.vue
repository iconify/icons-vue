<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfok_jgkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfok_jgkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:frame-light" /></template>
