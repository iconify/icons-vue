<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nseds-b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nseds-b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:album-2-line" /></template>
