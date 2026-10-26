<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-bp_jbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o-bp_jbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:bone-long-outline" /></template>
