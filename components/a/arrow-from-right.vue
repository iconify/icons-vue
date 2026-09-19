<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9keycb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9keycb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-from-right" /></template>
