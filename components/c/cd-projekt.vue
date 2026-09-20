<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdwo28b7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdwo28b7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:cd-projekt" /></template>
