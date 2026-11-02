<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5ggvfbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w5ggvfbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:hourglass-16-solid" /></template>
