<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpzn7xbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jpzn7xbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:dollar-increase-remix" /></template>
