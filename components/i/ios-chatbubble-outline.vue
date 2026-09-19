<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3poo6bbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o3poo6bbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-chatbubble-outline" /></template>
