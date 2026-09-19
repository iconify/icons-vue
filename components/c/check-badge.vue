<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swrqdc1lc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swrqdc1lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:check-badge" /></template>
