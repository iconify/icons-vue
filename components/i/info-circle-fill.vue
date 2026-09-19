<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sctsf2b8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sctsf2b8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:info-circle-fill" /></template>
