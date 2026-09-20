<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6-_visne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6-_visne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-right-wide-fill" /></template>
