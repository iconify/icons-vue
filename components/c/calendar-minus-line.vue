<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j089isygs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j089isygs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-minus-line" /></template>
