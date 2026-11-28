<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u874oxb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u874oxb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:files-search" /></template>
