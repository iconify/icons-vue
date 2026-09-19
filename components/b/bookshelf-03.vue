<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhk-rd3yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhk-rd3yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bookshelf-03" /></template>
