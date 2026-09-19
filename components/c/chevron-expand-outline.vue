<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7__n93bc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o7__n93bc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:chevron-expand-outline" /></template>
