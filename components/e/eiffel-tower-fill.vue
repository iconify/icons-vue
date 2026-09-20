<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggbogeabh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ggbogeabh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:eiffel-tower-fill" /></template>
