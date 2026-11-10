<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax-j1ibyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax-j1ibyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:calendar-filled" /></template>
