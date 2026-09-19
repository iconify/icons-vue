<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnd22ob2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wnd22ob2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-top-left-1-fill" /></template>
