<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do713mb7p.css';
import '../../css/w/wft5owbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="do713mb7p"/><path class="wft5owbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:frustrated2" /></template>
