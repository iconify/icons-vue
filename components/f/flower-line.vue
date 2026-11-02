<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmx0jjb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmx0jjb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flower-line" /></template>
