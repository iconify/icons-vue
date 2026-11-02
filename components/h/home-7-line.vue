<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvdlufc4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvdlufc4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:home-7-line" /></template>
