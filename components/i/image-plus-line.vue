<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-0odbcwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-0odbcwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:image-plus-line" /></template>
