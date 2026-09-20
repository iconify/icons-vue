<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlwa5nbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlwa5nbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrow-right-left" /></template>
