<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2jtk7bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f2jtk7bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:calendar-minus-outline" /></template>
