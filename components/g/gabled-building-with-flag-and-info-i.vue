<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx3qwj2_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xx3qwj2_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gabled-building-with-flag-and-info-i" /></template>
