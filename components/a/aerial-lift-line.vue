<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orqdep5yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orqdep5yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:aerial-lift-line" /></template>
