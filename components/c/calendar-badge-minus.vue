<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdu_9bchp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="cdu_9bchp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:calendar-badge-minus" /></template>
