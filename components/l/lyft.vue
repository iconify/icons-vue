<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7xcoth-m.css';
import '../../css/x/x-5p19nze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7xcoth-m"/><path class="x-5p19nze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:lyft" /></template>
