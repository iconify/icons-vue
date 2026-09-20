<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-y74lb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-y74lb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:chart-area-outline" /></template>
