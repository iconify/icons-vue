<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-29nt30n.css';
import '../../css/s/sj5ux4q1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m-29nt30n"/><path class="sj5ux4q1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-up-to-line-48-bold" /></template>
