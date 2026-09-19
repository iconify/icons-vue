<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxg0rzbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxg0rzbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:dots-grid-3x3" /></template>
