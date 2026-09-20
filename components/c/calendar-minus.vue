<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqkktjb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eqkktjb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:calendar-minus" /></template>
