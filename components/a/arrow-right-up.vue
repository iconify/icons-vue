<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k915ggbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k915ggbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:arrow-right-up" /></template>
