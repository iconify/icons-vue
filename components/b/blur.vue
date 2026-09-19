<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_-2k6bgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":416};
const content = `<path class="s_-2k6bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:blur" /></template>
