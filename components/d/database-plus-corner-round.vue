<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0nx-b4na.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0nx-b4na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:database-plus-corner-round" /></template>
