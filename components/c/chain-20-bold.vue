<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agoxzxbge.css';
import '../../css/m/mb2ru1gou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="agoxzxbge"/><path class="mb2ru1gou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chain-20-bold" /></template>
