<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb6theb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hb6theb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bank2" /></template>
