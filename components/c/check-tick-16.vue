<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz2jks-da.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vz2jks-da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:check-tick-16" /></template>
