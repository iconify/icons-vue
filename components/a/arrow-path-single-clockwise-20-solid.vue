<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iytxjw3_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="iytxjw3_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-path-single-clockwise-20-solid" /></template>
