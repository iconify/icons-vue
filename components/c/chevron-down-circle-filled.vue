<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfg6e8b5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfg6e8b5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chevron-down-circle-filled" /></template>
