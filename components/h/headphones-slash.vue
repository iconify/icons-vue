<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uar1gl6yh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uar1gl6yh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:headphones-slash" /></template>
