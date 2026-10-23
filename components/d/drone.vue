<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq4t0w1th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq4t0w1th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:drone" /></template>
