<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eohmfjb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eohmfjb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:lightbulb-fill" /></template>
