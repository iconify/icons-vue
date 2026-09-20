<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz3eg4bhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oz3eg4bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:level-left-bold" /></template>
