<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je9vfbbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je9vfbbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fish-off-line" /></template>
