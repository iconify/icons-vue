<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d85rrob6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d85rrob6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:arrow-circle-down" /></template>
