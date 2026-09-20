<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-h66ov0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="w-h66ov0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:address" /></template>
