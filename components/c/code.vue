<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thw5170-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thw5170-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:code" /></template>
