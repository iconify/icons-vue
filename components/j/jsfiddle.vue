<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghmu80r0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghmu80r0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:jsfiddle" /></template>
