<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke8gj0i4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ke8gj0i4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:distribute-vertical-48-bold" /></template>
