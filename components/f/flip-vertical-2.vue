<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr95f2b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr95f2b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:flip-vertical-2" /></template>
