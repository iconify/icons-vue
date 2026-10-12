<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjevk5tdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rjevk5tdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:child-48" /></template>
