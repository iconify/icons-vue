<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkrksc79e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkrksc79e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:grip-horizontal-line" /></template>
