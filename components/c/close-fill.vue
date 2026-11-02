<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6_9cnp8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6_9cnp8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:close-fill" /></template>
