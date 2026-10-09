<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkwo4-r4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kkwo4-r4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:loader-2-48" /></template>
