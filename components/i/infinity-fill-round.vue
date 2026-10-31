<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rew2wgbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rew2wgbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:infinity-fill-round" /></template>
