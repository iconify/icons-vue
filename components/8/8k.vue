<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj0jfeobs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="lj0jfeobs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:8k" /></template>
