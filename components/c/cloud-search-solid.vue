<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it8jh6fid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it8jh6fid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-search-solid" /></template>
