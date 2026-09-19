<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2d1b9c7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2d1b9c7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:align-vertical-distribute-start" /></template>
