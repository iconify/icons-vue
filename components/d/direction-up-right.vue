<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdn3qrb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="wdn3qrb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:direction-up-right" /></template>
