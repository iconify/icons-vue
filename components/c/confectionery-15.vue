<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je17il--x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="je17il--x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:confectionery-15" /></template>
