<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgt6-fbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgt6-fbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:lightbulb-outline" /></template>
