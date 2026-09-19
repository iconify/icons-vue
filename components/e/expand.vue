<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quteprb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="quteprb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:expand" /></template>
