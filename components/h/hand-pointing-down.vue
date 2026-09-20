<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_-eyrb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_-eyrb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hand-pointing-down" /></template>
