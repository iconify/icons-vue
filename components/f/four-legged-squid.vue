<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgxb__bke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wgxb__bke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:four-legged-squid" /></template>
