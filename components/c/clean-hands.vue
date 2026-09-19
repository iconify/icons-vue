<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vclhrnvfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vclhrnvfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:clean-hands" /></template>
