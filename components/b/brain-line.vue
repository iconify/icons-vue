<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoe7uff-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zoe7uff-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:brain-line" /></template>
