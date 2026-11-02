<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_0kplbow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_0kplbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-minus-2-fill" /></template>
