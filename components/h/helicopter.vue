<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8whn7b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8whn7b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:helicopter" /></template>
