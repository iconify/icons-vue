<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu6qnqe0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xu6qnqe0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:doublet-filled" /></template>
