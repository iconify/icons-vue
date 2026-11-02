<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9dj5s2vj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9dj5s2vj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:combine-2-fill" /></template>
