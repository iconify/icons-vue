<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr9c4dsmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr9c4dsmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:funnel-plus" /></template>
