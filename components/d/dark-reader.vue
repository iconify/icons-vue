<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9gfbgg9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9gfbgg9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:dark-reader" /></template>
