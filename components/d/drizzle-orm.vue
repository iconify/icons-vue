<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br5j05_gi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br5j05_gi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:drizzle-orm" /></template>
