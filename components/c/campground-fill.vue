<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm4rvkc0n.css';
import '../../css/p/p1djqlbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm4rvkc0n"/><path class="p1djqlbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:campground-fill" /></template>
