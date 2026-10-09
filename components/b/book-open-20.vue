<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlk1-zbma.css';
import '../../css/l/l016wdj-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rlk1-zbma"/><path class="l016wdj-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:book-open-20" /></template>
