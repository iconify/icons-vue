<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycgy5nb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycgy5nb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrows-pointing-in" /></template>
