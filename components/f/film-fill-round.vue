<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku_6aac1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku_6aac1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:film-fill-round" /></template>
