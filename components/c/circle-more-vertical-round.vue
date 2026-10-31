<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvy2xtale.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvy2xtale"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-more-vertical-round" /></template>
