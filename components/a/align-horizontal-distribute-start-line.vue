<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp35fxpuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp35fxpuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-horizontal-distribute-start-line" /></template>
