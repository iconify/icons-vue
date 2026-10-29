<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/deq0jmbdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="deq0jmbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:align-left-duo" /></template>
