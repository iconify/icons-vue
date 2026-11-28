<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw7a44n3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xw7a44n3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:lightbulb-question" /></template>
