<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws4hu2e0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ws4hu2e0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:caret-up-circle" /></template>
