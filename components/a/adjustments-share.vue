<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgj33abyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgj33abyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:adjustments-share" /></template>
