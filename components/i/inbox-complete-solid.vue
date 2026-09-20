<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3hw_dbub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m3hw_dbub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:inbox-complete-solid" /></template>
