<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnp7lfboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnp7lfboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:house-floor-lower" /></template>
