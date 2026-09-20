<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp1v9ybmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sp1v9ybmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:hotel-bed-2-remix" /></template>
