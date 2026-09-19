<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vclarl8ed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="vclarl8ed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:check-to-slot" /></template>
