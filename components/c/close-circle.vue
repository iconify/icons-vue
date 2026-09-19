<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6ig2cc8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="e6ig2cc8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:close-circle" /></template>
