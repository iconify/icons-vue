<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvuoqfmio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gvuoqfmio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:inbox-solid" /></template>
