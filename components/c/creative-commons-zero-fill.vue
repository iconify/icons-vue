<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3te10bus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3te10bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:creative-commons-zero-fill" /></template>
