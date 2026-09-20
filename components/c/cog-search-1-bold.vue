<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv572stwh.css';
import '../../css/n/nee9o4w2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv572stwh"/><path class="nee9o4w2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:cog-search-1-bold" /></template>
