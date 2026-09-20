<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnz4h-flh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnz4h-flh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:group-outline" /></template>
