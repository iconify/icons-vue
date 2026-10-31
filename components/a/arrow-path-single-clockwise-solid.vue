<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipyreya2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ipyreya2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-path-single-clockwise-solid" /></template>
