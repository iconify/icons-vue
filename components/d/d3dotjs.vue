<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqnv71b_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqnv71b_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:d3dotjs" /></template>
