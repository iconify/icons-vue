<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6hbulb-g.css';
import '../../css/t/tcuq2ituc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j6hbulb-g"/><path class="tcuq2ituc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:left-down2" /></template>
