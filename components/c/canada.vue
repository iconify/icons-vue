<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m__q8jbmq.css';
import '../../css/e/eft4hdbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="m__q8jbmq"/><path class="eft4hdbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:canada" /></template>
