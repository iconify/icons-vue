<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqje01ayu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jqje01ayu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:green-steel-48" /></template>
