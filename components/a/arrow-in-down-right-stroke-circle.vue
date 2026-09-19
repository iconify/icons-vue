<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxsk1y4aw.css';
import '../../css/f/fuq627b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxsk1y4aw"/><path class="fuq627b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-down-right-stroke-circle" /></template>
