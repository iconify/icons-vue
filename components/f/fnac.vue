<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr4wy349f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr4wy349f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fnac" /></template>
