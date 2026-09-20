<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9wyl3bfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9wyl3bfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cloud-rain" /></template>
