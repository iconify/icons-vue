<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9ezq80-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9ezq80-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:battery-4-line" /></template>
