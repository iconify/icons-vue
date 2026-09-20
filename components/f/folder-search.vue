<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l09wnubxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l09wnubxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:folder-search" /></template>
