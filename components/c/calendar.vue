<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1vvqxbbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="p1vvqxbbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:calendar" /></template>
