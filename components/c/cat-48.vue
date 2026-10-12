<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozo7glmpq.css';
import '../../css/s/svf74obkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ozo7glmpq"/><path class="svf74obkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cat-48" /></template>
