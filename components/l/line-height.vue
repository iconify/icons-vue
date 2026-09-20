<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg11x4bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg11x4bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:line-height" /></template>
