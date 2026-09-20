<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6i5ey9la.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6i5ey9la"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-minus-outline" /></template>
