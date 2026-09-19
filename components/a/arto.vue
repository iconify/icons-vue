<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfswnh5af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":488};
const content = `<path class="cfswnh5af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:arto" /></template>
