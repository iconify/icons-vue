<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvpt0wbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvpt0wbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:combine-fill" /></template>
