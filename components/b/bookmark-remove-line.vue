<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3n3mnbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3n3mnbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bookmark-remove-line" /></template>
