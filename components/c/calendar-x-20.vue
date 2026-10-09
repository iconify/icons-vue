<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-bc1ybft.css';
import '../../css/r/rqm6u7mkv.css';
import '../../css/t/t8og4ac6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f-bc1ybft"/><path class="rqm6u7mkv"/><path class="t8og4ac6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calendar-x-20" /></template>
