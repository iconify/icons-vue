<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxe6n8b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qxe6n8b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:circle" /></template>
