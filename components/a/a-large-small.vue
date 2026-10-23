<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wask6o2nq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wask6o2nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:a-large-small" /></template>
