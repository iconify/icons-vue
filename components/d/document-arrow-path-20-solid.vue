<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3pubybgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="i3pubybgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:document-arrow-path-20-solid" /></template>
