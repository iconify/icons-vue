<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxudl40-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxudl40-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-big-right" /></template>
