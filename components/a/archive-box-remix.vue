<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt1k-qwgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nt1k-qwgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:archive-box-remix" /></template>
