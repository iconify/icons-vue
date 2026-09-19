<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epgk7ub8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="epgk7ub8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:cogs" /></template>
