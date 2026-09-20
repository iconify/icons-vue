<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2miiia8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h2miiia8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:calendar-outline" /></template>
