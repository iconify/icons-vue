<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv380lbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rv380lbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-text-fill-round" /></template>
