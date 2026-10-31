<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_s7w5bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_s7w5bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-search-corner-fill-round" /></template>
