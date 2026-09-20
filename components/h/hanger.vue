<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iglyc9bzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iglyc9bzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:hanger" /></template>
