<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1fsbgbhg.css';
import '../../css/a/aned6khuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1fsbgbhg"/><path class="aned6khuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:calendar-times" /></template>
