<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl1gwh6zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl1gwh6zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:archive-slash" /></template>
