<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0sbp1bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0sbp1bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-rotary-first-left" /></template>
