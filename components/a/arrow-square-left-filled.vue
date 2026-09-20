<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/degyop8_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="degyop8_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-square-left-filled" /></template>
