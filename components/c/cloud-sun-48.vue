<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkcnnbb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lkcnnbb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-sun-48" /></template>
