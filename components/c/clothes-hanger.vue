<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w13_1eb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w13_1eb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:clothes-hanger" /></template>
