<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m28-rvb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m28-rvb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:briefcase-with-info-i" /></template>
