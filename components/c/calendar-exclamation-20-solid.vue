<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py1c9c1oh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="py1c9c1oh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:calendar-exclamation-20-solid" /></template>
