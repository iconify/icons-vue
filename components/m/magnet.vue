<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ius746b1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ius746b1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:magnet" /></template>
