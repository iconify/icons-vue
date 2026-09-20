<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grmcd7z2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grmcd7z2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:add-circle-line" /></template>
