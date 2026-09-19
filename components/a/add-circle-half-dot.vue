<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll8z50eyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll8z50eyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:add-circle-half-dot" /></template>
