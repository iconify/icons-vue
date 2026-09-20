<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg2jysbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lg2jysbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:crescent" /></template>
