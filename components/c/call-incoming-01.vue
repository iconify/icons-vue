<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu0fn4-yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu0fn4-yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:call-incoming-01" /></template>
