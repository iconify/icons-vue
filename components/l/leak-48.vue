<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0lt8rbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j0lt8rbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:leak-48" /></template>
