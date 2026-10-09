<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njm7sdbty.css';
import '../../css/m/mazh1ozjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="njm7sdbty"/><path class="mazh1ozjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-open-48" /></template>
