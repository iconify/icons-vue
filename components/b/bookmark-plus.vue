<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa699oypj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa699oypj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:bookmark-plus" /></template>
