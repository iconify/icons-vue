<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1h-0dbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1h-0dbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:inequality-02" /></template>
