<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g48p0c9ak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g48p0c9ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clipboard-type-fill" /></template>
