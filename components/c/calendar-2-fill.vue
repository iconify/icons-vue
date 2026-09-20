<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0njmg14q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0njmg14q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-2-fill" /></template>
