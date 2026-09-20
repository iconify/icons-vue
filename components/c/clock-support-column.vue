<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plml1nb5a.css';
import '../../css/v/vgo3iyb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="plml1nb5a"/><path class="vgo3iyb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:clock-support-column" /></template>
