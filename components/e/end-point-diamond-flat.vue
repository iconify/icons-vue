<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn7azlbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hn7azlbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:end-point-diamond-flat" /></template>
