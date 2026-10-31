<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uakihh5sg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uakihh5sg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-u-turn-down-left-bulk-round" /></template>
