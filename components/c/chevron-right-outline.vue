<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc2hi3nnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc2hi3nnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:chevron-right-outline" /></template>
