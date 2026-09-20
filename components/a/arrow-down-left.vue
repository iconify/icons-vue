<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4s_8jz7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4s_8jz7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-down-left" /></template>
