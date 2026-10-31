<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvr3t2bex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvr3t2bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:armchair-round" /></template>
