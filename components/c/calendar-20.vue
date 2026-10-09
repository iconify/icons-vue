<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-bc1ybft.css';
import '../../css/f/f5keg8bhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f-bc1ybft"/><path class="f5keg8bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calendar-20" /></template>
