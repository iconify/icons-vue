<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8ad-p7us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b8ad-p7us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:download" /></template>
