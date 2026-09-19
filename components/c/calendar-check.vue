<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjz64c8ba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="vjz64c8ba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:calendar-check" /></template>
