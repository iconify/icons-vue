<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9npv1b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="h9npv1b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:line-height-small" /></template>
