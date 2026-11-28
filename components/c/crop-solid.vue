<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brk9uu4sq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brk9uu4sq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:crop-solid" /></template>
