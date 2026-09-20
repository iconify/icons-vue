<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-t-o1ivl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-t-o1ivl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cloud-star" /></template>
