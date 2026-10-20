<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aum7pfzqi.css';
import '../../css/s/s19zwtb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aum7pfzqi"/><path class="s19zwtb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calendar-star-20-bold" /></template>
