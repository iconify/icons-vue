<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1q_vfblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1q_vfblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:case-lower" /></template>
