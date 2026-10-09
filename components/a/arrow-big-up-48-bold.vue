<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdag1bnag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cdag1bnag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-big-up-48-bold" /></template>
