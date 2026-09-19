<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcoslgbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcoslgbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-message-alt-add" /></template>
