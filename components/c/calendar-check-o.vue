<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvp439bnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1792};
const content = `<path class="hvp439bnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:calendar-check-o" /></template>
