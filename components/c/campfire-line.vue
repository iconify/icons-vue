<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj5nxlerw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj5nxlerw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:campfire-line" /></template>
