<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obg_7yb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="obg_7yb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:line-arrow-turn-down-left-remix" /></template>
