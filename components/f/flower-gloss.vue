<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyium1yvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyium1yvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:flower-gloss" /></template>
