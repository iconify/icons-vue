<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b36-k-mqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b36-k-mqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:checks" /></template>
