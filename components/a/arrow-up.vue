<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cll3tvdmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cll3tvdmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-up" /></template>
