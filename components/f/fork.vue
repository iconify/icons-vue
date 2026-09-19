<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehgdjcc8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ehgdjcc8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:fork" /></template>
