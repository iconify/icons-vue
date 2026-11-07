<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmt8ryb3g.css';
import '../../css/u/uijvjtbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmt8ryb3g"/><path class="uijvjtbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chevrons-right-left-outline" /></template>
