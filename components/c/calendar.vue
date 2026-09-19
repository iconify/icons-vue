<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su1uxpbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="su1uxpbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:calendar" /></template>
