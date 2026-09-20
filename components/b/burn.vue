<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmu_cgbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="gmu_cgbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:burn" /></template>
