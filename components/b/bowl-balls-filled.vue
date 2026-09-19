<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so6vp6w1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so6vp6w1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bowl-balls-filled" /></template>
