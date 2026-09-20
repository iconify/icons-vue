<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs6nie1vq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs6nie1vq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-vertical-justify-center" /></template>
