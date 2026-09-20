<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtsxs0oef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtsxs0oef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-u-left-bottom" /></template>
