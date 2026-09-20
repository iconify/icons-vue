<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm_j1ib0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm_j1ib0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:arrow-downward-line" /></template>
