<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbs9_-1an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbs9_-1an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:api" /></template>
