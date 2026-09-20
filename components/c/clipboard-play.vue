<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-k8jwbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-k8jwbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-play" /></template>
