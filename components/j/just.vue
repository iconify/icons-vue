<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz4jzm5oa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vz4jzm5oa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:just" /></template>
