<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp4s2qblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sp4s2qblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:ellipsis-h-solid" /></template>
