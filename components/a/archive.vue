<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6v2zhbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":472};
const content = `<path class="r6v2zhbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:archive" /></template>
