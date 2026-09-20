<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcdd--2ea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcdd--2ea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:arrow-left-down-circle-filled" /></template>
