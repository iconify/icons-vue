<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1ooz0bja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m1ooz0bja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:checkbox-undeterminate-filled" /></template>
