<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngyvv5bhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ngyvv5bhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:battery-0" /></template>
