<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge6durbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ge6durbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-vertical-fill" /></template>
