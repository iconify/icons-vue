<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sen0zg3ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sen0zg3ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:handled-teacup" /></template>
