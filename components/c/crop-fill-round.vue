<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl88tvb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl88tvb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:crop-fill-round" /></template>
