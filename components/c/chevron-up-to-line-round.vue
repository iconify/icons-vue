<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gklbd6bzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gklbd6bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-up-to-line-round" /></template>
