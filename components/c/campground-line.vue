<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2_s-fbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2_s-fbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:campground-line" /></template>
