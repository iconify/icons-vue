<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on3bxby9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="on3bxby9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:close-small" /></template>
