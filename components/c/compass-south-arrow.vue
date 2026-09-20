<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjptze3sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="yjptze3sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:compass-south-arrow" /></template>
