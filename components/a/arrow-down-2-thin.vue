<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5h_ypb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5h_ypb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-down-2-thin" /></template>
