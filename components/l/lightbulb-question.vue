<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3eylgbnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3eylgbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:lightbulb-question" /></template>
