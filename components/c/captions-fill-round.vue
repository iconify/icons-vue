<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v03fs2b-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v03fs2b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:captions-fill-round" /></template>
