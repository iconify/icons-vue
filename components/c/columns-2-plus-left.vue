<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz97d6w4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz97d6w4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:columns-2-plus-left" /></template>
