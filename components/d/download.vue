<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7pcs3b4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":384};
const content = `<path class="y7pcs3b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:download" /></template>
