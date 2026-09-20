<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz-qdgbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz-qdgbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:chevron-left-outline" /></template>
