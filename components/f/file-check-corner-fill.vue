<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz6x1qi_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz6x1qi_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-check-corner-fill" /></template>
