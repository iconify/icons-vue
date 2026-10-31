<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf2eypbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kf2eypbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-double-right-fill-round" /></template>
