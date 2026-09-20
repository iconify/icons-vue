<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqglfy7gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqglfy7gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-narrow-right-dashed" /></template>
