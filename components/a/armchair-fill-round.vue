<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-wtnuboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-wtnuboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:armchair-fill-round" /></template>
