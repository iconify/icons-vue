<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdme6km3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="kdme6km3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:circle-small" /></template>
