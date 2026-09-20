<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_hod8bja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="d_hod8bja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:key" /></template>
