<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az_a87o8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="az_a87o8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:file-vector" /></template>
