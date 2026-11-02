<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un28y8tbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un28y8tbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:badge-octagram-fill" /></template>
