<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgc4gwb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgc4gwb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gift-card-fill" /></template>
