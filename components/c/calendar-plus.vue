<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7wj43brc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="r7wj43brc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:calendar-plus" /></template>
