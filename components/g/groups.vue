<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdbww45vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sdbww45vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:groups" /></template>
