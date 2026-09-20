<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2k0_cbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o2k0_cbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-down-from-rectangle-outline" /></template>
