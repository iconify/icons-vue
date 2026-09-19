<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3kb6gbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3kb6gbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:bold" /></template>
