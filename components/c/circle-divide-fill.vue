<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjqd8mbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjqd8mbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-divide-fill" /></template>
