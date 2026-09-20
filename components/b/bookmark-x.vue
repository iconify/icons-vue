<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj5wg5fxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj5wg5fxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:bookmark-x" /></template>
