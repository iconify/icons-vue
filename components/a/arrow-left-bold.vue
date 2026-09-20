<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s43x5mb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s43x5mb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-left-bold" /></template>
