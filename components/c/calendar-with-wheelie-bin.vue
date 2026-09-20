<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to-4c9b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="to-4c9b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:calendar-with-wheelie-bin" /></template>
