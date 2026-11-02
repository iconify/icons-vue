<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlxrqwa7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlxrqwa7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:door-line" /></template>
