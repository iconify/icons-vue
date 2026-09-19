<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku8f-qb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ku8f-qb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:fried-egg" /></template>
