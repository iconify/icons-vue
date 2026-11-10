<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5l9-mb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="p5l9-mb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:calendar-check-20-solid" /></template>
