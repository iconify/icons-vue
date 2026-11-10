<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmn17dblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xmn17dblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:bookmark-x-mark-20-solid" /></template>
