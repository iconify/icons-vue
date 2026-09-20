<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwcv33b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iwcv33b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bookmark-square2" /></template>
