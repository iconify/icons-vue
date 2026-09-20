<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euzmmobsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="euzmmobsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:calendar-check" /></template>
