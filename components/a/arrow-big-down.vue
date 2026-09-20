<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g33muxbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g33muxbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-big-down" /></template>
